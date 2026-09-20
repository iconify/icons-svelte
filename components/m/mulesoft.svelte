<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkom-ab6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkom-ab6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mulesoft" {...props}></Icon>
