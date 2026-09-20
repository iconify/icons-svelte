<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4fi4u11f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4fi4u11f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:metro-de-madrid" {...props}></Icon>
