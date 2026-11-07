<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrxlgg64z.css';
import '../../css/i/i6gu3rbfq.css';
import '../../css/z/zxzmymb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="i6gu3rbfq"/><path class="zxzmymb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-new-round-bold-duotone" {...props}></Icon>
