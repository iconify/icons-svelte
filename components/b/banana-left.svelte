<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p--21yv0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="p--21yv0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:banana-left" {...props}></Icon>
