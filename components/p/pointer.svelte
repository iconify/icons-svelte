<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h40qtf6_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h40qtf6_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pointer" {...props}></Icon>
