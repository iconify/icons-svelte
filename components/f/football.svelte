<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaqvmrv5k.css';
import '../../css/p/pd26jybbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaqvmrv5k"/><path class="pd26jybbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:football" {...props}></Icon>
