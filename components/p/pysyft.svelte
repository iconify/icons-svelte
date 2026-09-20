<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/injrr7bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="injrr7bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pysyft" {...props}></Icon>
