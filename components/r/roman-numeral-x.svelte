<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8ica_bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g8ica_bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-x" {...props}></Icon>
