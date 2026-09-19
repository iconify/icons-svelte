<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvradzqdb.css';
import '../../css/y/yvl9v5b9e.css';
import '../../css/p/psjdr85ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cvradzqdb"/><path class="yvl9v5b9e"/><path class="psjdr85ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:async" {...props}></Icon>
