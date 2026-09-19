<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd3l-rb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vd3l-rb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-expand" {...props}></Icon>
