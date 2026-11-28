<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvynwcrpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvynwcrpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ev-charger-clock" {...props}></Icon>
