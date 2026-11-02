<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orz21ab4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orz21ab4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:record-mail-fill" {...props}></Icon>
