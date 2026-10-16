<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lam0-jatz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lam0-jatz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-up-down-20-bold" {...props}></Icon>
