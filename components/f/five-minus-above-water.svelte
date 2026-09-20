<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt-nhpvlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zt-nhpvlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:five-minus-above-water" {...props}></Icon>
