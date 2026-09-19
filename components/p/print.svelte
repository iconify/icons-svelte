<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w33lbnb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="w33lbnb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:print" {...props}></Icon>
