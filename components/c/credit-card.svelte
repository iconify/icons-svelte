<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2_zngbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="a2_zngbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:credit-card" {...props}></Icon>
