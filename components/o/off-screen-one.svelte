<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trxsf6g2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="trxsf6g2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:off-screen-one" {...props}></Icon>
