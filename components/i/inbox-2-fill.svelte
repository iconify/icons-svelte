<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_m9--2rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_m9--2rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inbox-2-fill" {...props}></Icon>
