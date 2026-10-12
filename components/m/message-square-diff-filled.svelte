<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc7v2ekmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sc7v2ekmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-diff-filled" {...props}></Icon>
