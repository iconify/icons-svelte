<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb8yjtcyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb8yjtcyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:anti-lock-braking-system" {...props}></Icon>
