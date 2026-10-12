<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0zdwccrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l0zdwccrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-fill-20" {...props}></Icon>
