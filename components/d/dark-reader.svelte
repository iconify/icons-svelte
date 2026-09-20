<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0j_4n65t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0j_4n65t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dark-reader" {...props}></Icon>
