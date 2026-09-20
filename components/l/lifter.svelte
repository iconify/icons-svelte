<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iutr1k6lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iutr1k6lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:lifter" {...props}></Icon>
