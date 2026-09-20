<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn1qe8dtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="pn1qe8dtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:minus" {...props}></Icon>
