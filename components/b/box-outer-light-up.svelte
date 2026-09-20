<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm644_2yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gm644_2yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up" {...props}></Icon>
