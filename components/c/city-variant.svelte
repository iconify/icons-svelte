<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n89iqcb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n89iqcb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:city-variant" {...props}></Icon>
