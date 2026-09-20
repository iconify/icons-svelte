<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2yv7bc5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2yv7bc5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:juke" {...props}></Icon>
