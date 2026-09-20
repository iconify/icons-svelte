<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-k9vbclp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-k9vbclp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coins" {...props}></Icon>
