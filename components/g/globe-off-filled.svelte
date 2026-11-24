<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk1iewbti.css';
import '../../css/q/ql1midcyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk1iewbti"/><path class="ql1midcyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-off-filled" {...props}></Icon>
