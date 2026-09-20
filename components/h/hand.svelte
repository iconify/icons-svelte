<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8-mjibvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8-mjibvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hand" {...props}></Icon>
