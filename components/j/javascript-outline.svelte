<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez09jybdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ez09jybdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:javascript-outline" {...props}></Icon>
