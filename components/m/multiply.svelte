<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y14ex5bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="y14ex5bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:multiply" {...props}></Icon>
