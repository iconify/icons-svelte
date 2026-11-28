<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eao-mibhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eao-mibhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bank-check" {...props}></Icon>
