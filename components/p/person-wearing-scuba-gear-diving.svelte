<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q28dagboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q28dagboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-scuba-gear-diving" {...props}></Icon>
