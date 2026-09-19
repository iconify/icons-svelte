<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t36tfl4ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t36tfl4ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:paint-brush" {...props}></Icon>
