<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9ndoqbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":371};
const content = `<path class="l9ndoqbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:decathlon-logo" {...props}></Icon>
