<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6099ob0e.css';
import '../../css/h/hjmckqb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6099ob0e"/><path class="hjmckqb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aimass" {...props}></Icon>
