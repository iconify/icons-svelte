<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq3c7540h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq3c7540h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:math-minus" {...props}></Icon>
