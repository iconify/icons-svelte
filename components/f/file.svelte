<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erj8o9bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="erj8o9bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:file" {...props}></Icon>
