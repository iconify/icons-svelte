<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt4-etjxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":448};
const content = `<path class="yt4-etjxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:radio-empty" {...props}></Icon>
