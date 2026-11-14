<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue1wbd4-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue1wbd4-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:euro-eur" {...props}></Icon>
