<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqfo8ifwt.css';
import '../../css/e/ef42dcbgs.css';
import '../../css/a/azuny7xti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqfo8ifwt"/><path class="ef42dcbgs"/><path class="azuny7xti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:chart-line" {...props}></Icon>
