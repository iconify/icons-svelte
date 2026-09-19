<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1eq-d3wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a1eq-d3wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bus-night" {...props}></Icon>
