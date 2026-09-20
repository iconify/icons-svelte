<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-7ueksdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a-7ueksdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:clock-person" {...props}></Icon>
