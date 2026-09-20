<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i94fbpbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i94fbpbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invio-dark" {...props}></Icon>
