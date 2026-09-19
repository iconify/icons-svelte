<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2pux81mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2pux81mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-compare-filled" {...props}></Icon>
