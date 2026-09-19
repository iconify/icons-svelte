<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oywppeflk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oywppeflk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-microphone" {...props}></Icon>
