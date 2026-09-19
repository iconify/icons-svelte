<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxq0p3_iq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zxq0p3_iq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bless" {...props}></Icon>
