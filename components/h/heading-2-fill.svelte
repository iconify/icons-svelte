<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu16d-u3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu16d-u3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-2-fill" {...props}></Icon>
