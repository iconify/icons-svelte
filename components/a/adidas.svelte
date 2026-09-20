<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd4u15bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd4u15bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:adidas" {...props}></Icon>
