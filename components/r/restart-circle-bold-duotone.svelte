<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrxlgg64z.css';
import '../../css/g/g5ezogbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="g5ezogbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:restart-circle-bold-duotone" {...props}></Icon>
