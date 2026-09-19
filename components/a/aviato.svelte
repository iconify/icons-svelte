<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b92jmp90d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="b92jmp90d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:aviato" {...props}></Icon>
