<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jackfjb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jackfjb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:attachments-filled" {...props}></Icon>
