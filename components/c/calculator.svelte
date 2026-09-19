<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa5g3utqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xa5g3utqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:calculator" {...props}></Icon>
