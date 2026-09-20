<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or6uk3bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="or6uk3bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:java-script" {...props}></Icon>
