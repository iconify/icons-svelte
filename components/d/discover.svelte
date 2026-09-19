<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk-_s_bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lk-_s_bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:discover" {...props}></Icon>
