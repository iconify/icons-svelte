<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzx0rv3rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzx0rv3rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mobile-me-logo-block" {...props}></Icon>
