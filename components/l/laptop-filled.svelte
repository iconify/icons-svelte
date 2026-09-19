<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzo0z4img.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzo0z4img"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:laptop-filled" {...props}></Icon>
