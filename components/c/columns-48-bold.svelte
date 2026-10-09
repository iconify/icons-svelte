<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy7xqk_um.css';
import '../../css/e/esgmmdbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xy7xqk_um"/><path class="esgmmdbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:columns-48-bold" {...props}></Icon>
