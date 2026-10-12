<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vehapbczu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="vehapbczu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:progress-empty" {...props}></Icon>
