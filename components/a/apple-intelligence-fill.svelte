<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flg4ghb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flg4ghb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:apple-intelligence-fill" {...props}></Icon>
