<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu2ac0b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu2ac0b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-from-dot-line" {...props}></Icon>
