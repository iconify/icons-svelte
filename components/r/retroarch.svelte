<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mebtap2fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mebtap2fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:retroarch" {...props}></Icon>
