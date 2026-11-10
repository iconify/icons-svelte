<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkx-nwsxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkx-nwsxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:error-502" {...props}></Icon>
