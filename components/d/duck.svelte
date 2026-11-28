<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/micyq1blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="micyq1blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:duck" {...props}></Icon>
