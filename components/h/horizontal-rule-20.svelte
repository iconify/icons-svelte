<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn4p0rgtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pn4p0rgtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:horizontal-rule-20" {...props}></Icon>
