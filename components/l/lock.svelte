<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_diomx1n.css';
import '../../css/d/dki33cb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="o_diomx1n"/><path class="dki33cb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:lock" {...props}></Icon>
