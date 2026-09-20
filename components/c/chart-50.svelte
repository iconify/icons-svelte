<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j81z2yx1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j81z2yx1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chart-50" {...props}></Icon>
