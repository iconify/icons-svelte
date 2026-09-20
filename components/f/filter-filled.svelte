<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utxk3l1jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utxk3l1jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:filter-filled" {...props}></Icon>
