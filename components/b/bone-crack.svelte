<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqgu-6_kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqgu-6_kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bone-crack" {...props}></Icon>
