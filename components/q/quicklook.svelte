<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjqif3zmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjqif3zmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:quicklook" {...props}></Icon>
