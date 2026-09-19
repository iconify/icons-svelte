<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tta7sbo4k.css';
import '../../css/v/vwq36dbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tta7sbo4k"/><path class="vwq36dbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:credit-card-outline" {...props}></Icon>
