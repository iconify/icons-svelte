<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dap5e4boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dap5e4boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:edit-alt-solid" {...props}></Icon>
