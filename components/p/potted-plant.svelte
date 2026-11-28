<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf_rons6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf_rons6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:potted-plant" {...props}></Icon>
