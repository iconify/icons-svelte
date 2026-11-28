<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jntxs735o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jntxs735o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:border-bottom-solid" {...props}></Icon>
