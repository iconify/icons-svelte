<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9l0blbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9l0blbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dragonframe" {...props}></Icon>
