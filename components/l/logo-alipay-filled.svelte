<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sklr68b5u.css';
import '../../css/r/rkkr41y9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sklr68b5u"/><path class="rkkr41y9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-alipay-filled" {...props}></Icon>
