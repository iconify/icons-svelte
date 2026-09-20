<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoiowgbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoiowgbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lospec" {...props}></Icon>
