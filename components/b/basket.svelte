<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi62vwbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zi62vwbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:basket" {...props}></Icon>
