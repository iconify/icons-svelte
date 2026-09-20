<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt17g7bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt17g7bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:google-lens" {...props}></Icon>
