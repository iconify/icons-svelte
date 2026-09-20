<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrxlgg64z.css';
import '../../css/h/hzgg3n9zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="hzgg3n9zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:clock-two" {...props}></Icon>
