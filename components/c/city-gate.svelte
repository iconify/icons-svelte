<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enjjb4y7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="enjjb4y7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:city-gate" {...props}></Icon>
