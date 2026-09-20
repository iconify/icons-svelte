<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og2u-rb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og2u-rb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-plus-outline" {...props}></Icon>
