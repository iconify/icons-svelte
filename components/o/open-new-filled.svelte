<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8mx9__7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s8mx9__7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:open-new-filled" {...props}></Icon>
