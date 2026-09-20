<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev6d5gw2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev6d5gw2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notebook-fill" {...props}></Icon>
