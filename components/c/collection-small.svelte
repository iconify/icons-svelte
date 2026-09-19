<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl0qf53pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="fl0qf53pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:collection-small" {...props}></Icon>
