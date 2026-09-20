<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsxp_0bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsxp_0bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-solana" {...props}></Icon>
