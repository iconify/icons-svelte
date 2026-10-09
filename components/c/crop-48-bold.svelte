<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5slb8bxt.css';
import '../../css/l/lukcxwqgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e5slb8bxt"/><path class="lukcxwqgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crop-48-bold" {...props}></Icon>
