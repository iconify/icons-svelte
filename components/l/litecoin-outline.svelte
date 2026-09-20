<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1frgq2nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f1frgq2nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:litecoin-outline" {...props}></Icon>
