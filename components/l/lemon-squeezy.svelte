<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuo09szyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":28};
const content = `<path clip-rule="evenodd" class="cuo09szyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lemon-squeezy" {...props}></Icon>
