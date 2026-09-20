<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz-_5oksg.css';
import '../../css/s/snpiwsb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="sz-_5oksg"/><circle class="snpiwsb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:blue-circle" {...props}></Icon>
