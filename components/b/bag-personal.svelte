<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y86geebsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="y86geebsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:bag-personal" {...props}></Icon>
