<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlhgx7bdi.css';
import '../../css/n/nx3hbtbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="zlhgx7bdi"/><path class="nx3hbtbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:refresh" {...props}></Icon>
