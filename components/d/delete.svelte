<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3ljxyeyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="j3ljxyeyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:delete" {...props}></Icon>
