<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py4unwgmu.css';
import '../../css/a/aqlii8bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":87.197};
const content = `<path class="py4unwgmu"/><path class="aqlii8bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nocobase-light" {...props}></Icon>
