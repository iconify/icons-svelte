<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5-mwfuyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="l5-mwfuyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:money-bill-wave-alt" {...props}></Icon>
