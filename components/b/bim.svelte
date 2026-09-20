<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsu1bjbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsu1bjbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bim" {...props}></Icon>
