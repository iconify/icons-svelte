<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3kdwwbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o3kdwwbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:bun" {...props}></Icon>
