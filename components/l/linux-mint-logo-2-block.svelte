<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrd_d7bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vrd_d7bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:linux-mint-logo-2-block" {...props}></Icon>
