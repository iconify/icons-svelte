<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lld8wpyib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lld8wpyib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:passport" {...props}></Icon>
