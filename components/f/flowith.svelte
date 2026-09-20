<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_s-f_7kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_s-f_7kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flowith" {...props}></Icon>
