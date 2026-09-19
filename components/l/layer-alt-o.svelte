<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6oibxtkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d6oibxtkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-alt-o" {...props}></Icon>
