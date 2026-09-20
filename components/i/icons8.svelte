<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_lg19ylu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_lg19ylu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:icons8" {...props}></Icon>
