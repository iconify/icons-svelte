<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2i40wv8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f2i40wv8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:preregistered-tc" {...props}></Icon>
