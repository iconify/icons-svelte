<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo8dceitg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo8dceitg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nutanix" {...props}></Icon>
