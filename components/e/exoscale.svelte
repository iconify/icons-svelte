<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta_6slvwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta_6slvwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:exoscale" {...props}></Icon>
