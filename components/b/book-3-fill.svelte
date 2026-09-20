<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu06u1-hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uu06u1-hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-3-fill" {...props}></Icon>
