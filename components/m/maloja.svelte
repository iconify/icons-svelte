<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzvbfpb6b.css';
import '../../css/b/b81wimuvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uzvbfpb6b"/><path class="b81wimuvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maloja" {...props}></Icon>
