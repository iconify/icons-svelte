<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xicth8brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xicth8brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mta" {...props}></Icon>
