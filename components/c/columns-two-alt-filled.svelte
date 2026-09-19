<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3dr61y4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3dr61y4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:columns-two-alt-filled" {...props}></Icon>
