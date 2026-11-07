<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrxlgg64z.css';
import '../../css/q/qcdgl6btj.css';
import '../../css/e/e23ts40de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="qcdgl6btj"/><path class="e23ts40de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:earth-bold-duotone" {...props}></Icon>
