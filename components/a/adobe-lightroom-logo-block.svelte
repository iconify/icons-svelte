<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcnyw0x5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcnyw0x5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-lightroom-logo-block" {...props}></Icon>
