<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj6jfsbht.css';
import '../../css/z/zalemybnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wj6jfsbht"/><path class="zalemybnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:poultryleg" {...props}></Icon>
