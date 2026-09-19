<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz8i1bs_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iz8i1bs_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:color-fill" {...props}></Icon>
