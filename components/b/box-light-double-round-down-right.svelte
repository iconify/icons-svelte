<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx9uqkqgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tx9uqkqgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-round-down-right" {...props}></Icon>
