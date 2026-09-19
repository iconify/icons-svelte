<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un82zp0vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="un82zp0vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:i-brick" {...props}></Icon>
