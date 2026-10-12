<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msf46bcth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msf46bcth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-npr" {...props}></Icon>
