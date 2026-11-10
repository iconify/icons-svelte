<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3j1mcc8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3j1mcc8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:error-404" {...props}></Icon>
