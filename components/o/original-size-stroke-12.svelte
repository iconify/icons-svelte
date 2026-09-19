<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr19n4brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tr19n4brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:original-size-stroke-12" {...props}></Icon>
