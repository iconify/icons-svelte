<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b87w7g1jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b87w7g1jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:hail" {...props}></Icon>
