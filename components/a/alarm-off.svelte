<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1p--tj3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1p--tj3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:alarm-off" {...props}></Icon>
