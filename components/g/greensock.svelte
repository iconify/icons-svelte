<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnr844bya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnr844bya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:greensock" {...props}></Icon>
