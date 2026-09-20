<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtodnibgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xtodnibgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:desk-lamp-2-fill" {...props}></Icon>
