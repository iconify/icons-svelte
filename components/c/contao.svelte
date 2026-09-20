<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0-suklrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0-suklrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:contao" {...props}></Icon>
