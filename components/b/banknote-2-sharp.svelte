<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr2s0kvbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2s0kvbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-2-sharp" {...props}></Icon>
