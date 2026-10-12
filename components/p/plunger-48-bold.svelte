<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8v5izblz.css';
import '../../css/e/e_y__bbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z8v5izblz"/><path class="e_y__bbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plunger-48-bold" {...props}></Icon>
