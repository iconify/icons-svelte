<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9czz4bal.css';
import '../../css/e/ef_ersl9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d9czz4bal"/><path class="ef_ersl9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-48" {...props}></Icon>
