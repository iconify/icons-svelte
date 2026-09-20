<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h149-xhjx.css';
import '../../css/e/esvqany8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="h149-xhjx"/><path class="esvqany8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:angle-double-right" {...props}></Icon>
