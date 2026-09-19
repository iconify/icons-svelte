<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg-8bfyph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mg-8bfyph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:dinner-filled" {...props}></Icon>
