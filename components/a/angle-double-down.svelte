<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqhgy604n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqhgy604n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:angle-double-down" {...props}></Icon>
