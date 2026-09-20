<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grwne1bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<circle class="grwne1bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:circle" {...props}></Icon>
