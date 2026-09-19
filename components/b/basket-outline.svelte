<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2g2swbim.css';
import '../../css/f/f471phb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d2g2swbim"/><path class="f471phb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:basket-outline" {...props}></Icon>
