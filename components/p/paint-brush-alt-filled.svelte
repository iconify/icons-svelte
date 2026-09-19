<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7gypjs_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7gypjs_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:paint-brush-alt-filled" {...props}></Icon>
