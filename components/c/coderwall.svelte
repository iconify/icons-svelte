<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzpaq-eyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzpaq-eyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:coderwall" {...props}></Icon>
