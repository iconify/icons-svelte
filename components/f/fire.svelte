<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej-tn9ioj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ej-tn9ioj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:fire" {...props}></Icon>
