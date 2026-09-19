<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw7wxvlhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uw7wxvlhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-up-circle-fill" {...props}></Icon>
