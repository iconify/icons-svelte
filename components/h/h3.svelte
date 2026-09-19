<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp-an5bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp-an5bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:h3" {...props}></Icon>
