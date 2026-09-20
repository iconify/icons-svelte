<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx3fx-byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tx3fx-byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-boarding-car" {...props}></Icon>
