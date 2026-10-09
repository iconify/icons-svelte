<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9mb5epez.css';
import '../../css/o/ofnlx5qvz.css';
import '../../css/n/nciip6bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v9mb5epez"/><path class="ofnlx5qvz"/><path class="nciip6bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:move-48-bold" {...props}></Icon>
