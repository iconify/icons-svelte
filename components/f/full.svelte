<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssduyhgbk.css';
import '../../css/k/ktcdaovuf.css';
import '../../css/m/mwuopsbdz.css';
import '../../css/v/v2j0phshp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssduyhgbk"/><path class="ktcdaovuf"/><path class="mwuopsbdz"/><path class="v2j0phshp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:full" {...props}></Icon>
