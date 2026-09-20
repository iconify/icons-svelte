<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtt8x7bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5.5};
const content = `<path class="gtt8x7bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:google-plus" {...props}></Icon>
