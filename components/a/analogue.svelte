<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8eml_bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8eml_bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:analogue" {...props}></Icon>
