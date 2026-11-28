<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2wstabov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2wstabov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:boxes" {...props}></Icon>
