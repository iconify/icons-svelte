<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsmf72c3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsmf72c3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:etihadairways" {...props}></Icon>
