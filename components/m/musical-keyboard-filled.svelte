<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th-w9lb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="th-w9lb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:musical-keyboard-filled" {...props}></Icon>
