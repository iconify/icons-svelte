<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf8ov84ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf8ov84ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:code-2" {...props}></Icon>
