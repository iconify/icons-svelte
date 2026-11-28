<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxkixgb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jxkixgb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:olive" {...props}></Icon>
