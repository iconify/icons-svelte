<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t662f0tno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="t662f0tno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:credit-card" {...props}></Icon>
