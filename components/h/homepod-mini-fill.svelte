<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mub4bxbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mub4bxbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:homepod-mini-fill" {...props}></Icon>
