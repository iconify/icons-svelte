<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrxlgg64z.css';
import '../../css/e/er9_2_bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="er9_2_bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:circle-dot-bold-duotone" {...props}></Icon>
