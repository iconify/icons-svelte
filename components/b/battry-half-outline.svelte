<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqq2u8ckh.css';
import '../../css/m/mthptgvbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqq2u8ckh"/><path clip-rule="evenodd" class="mthptgvbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:battry-half-outline" {...props}></Icon>
