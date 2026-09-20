<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk7c0-brn.css';
import '../../css/b/bcoesb68t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk7c0-brn"/><path class="bcoesb68t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cog-hand-give-1-bold" {...props}></Icon>
