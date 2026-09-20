<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4xr0yhpn.css';
import '../../css/f/f2h708bjp.css';
import '../../css/c/c0k_mybxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4xr0yhpn"/><path class="f2h708bjp"/><path class="c0k_mybxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-1-filled" {...props}></Icon>
