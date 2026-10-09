<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j93ektbkr.css';
import '../../css/z/zf5iukb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j93ektbkr"/><path class="zf5iukb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:capacitor-48-bold" {...props}></Icon>
