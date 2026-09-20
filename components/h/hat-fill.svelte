<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li7an9b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="li7an9b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hat-fill" {...props}></Icon>
