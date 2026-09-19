<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u159h1bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u159h1bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:folder-filled" {...props}></Icon>
