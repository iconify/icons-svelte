<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmehbye3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmehbye3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-cup" {...props}></Icon>
