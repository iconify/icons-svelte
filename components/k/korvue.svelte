<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so9b0vatz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":446,"height":512};
const content = `<path class="so9b0vatz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:korvue" {...props}></Icon>
