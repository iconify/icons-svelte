<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luyue7b6t.css';
import '../../css/e/ew7h4abcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="luyue7b6t"/><path class="ew7h4abcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-headset" {...props}></Icon>
