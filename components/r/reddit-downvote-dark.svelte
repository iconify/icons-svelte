<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbwfuo6tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vbwfuo6tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reddit-downvote-dark" {...props}></Icon>
