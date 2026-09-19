<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg-6srbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="eg-6srbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-cycle-stroke-12" {...props}></Icon>
