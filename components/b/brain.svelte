<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efmf53bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efmf53bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:brain" {...props}></Icon>
