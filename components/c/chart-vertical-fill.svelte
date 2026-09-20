<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc0_cjb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc0_cjb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chart-vertical-fill" {...props}></Icon>
