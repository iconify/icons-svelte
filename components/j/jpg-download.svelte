<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ady3sabzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ady3sabzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:jpg-download" {...props}></Icon>
