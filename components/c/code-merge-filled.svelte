<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf324w_xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gf324w_xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-merge-filled" {...props}></Icon>
