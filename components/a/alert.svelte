<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5wxdzbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="l5wxdzbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:alert" {...props}></Icon>
