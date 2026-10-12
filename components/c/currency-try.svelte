<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7a2insdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7a2insdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-try" {...props}></Icon>
