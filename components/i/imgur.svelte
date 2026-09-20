<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm9_epbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm9_epbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:imgur" {...props}></Icon>
