<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akpl_7g_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="akpl_7g_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:diploma-check" {...props}></Icon>
