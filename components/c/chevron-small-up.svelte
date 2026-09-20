<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr2bya.css';
import '../../css/s/so-from-10.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2bya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-small-up" {...props}></Icon>
