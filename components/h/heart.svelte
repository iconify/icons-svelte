<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb6mwqofg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qb6mwqofg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:heart" {...props}></Icon>
