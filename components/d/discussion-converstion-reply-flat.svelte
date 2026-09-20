<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce-k3acqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ce-k3acqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:discussion-converstion-reply-flat" {...props}></Icon>
