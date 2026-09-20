<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcp0yebys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcp0yebys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-dot-sharp" {...props}></Icon>
