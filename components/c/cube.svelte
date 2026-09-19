<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvq1561eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvq1561eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:cube" {...props}></Icon>
