<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpwzb9bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fpwzb9bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-3-fill" {...props}></Icon>
