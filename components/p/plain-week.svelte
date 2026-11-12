<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpzvbnz3y.css';
import '../../css/t/tkao4yftb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="vpzvbnz3y"/><path class="tkao4yftb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plain-week" {...props}></Icon>
