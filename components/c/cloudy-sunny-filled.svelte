<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgm2whbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgm2whbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cloudy-sunny-filled" {...props}></Icon>
