<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix0kzerhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix0kzerhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-azn" {...props}></Icon>
