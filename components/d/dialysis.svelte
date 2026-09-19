<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apb9iiktg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="apb9iiktg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dialysis" {...props}></Icon>
