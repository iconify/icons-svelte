<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4xr0yhpn.css';
import '../../css/w/wxkzprrkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4xr0yhpn"/><path class="wxkzprrkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-adobe-illustrate-filled" {...props}></Icon>
