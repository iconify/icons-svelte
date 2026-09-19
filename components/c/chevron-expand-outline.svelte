<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7__n93bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7__n93bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chevron-expand-outline" {...props}></Icon>
