<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/advjs7-_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="advjs7-_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:meta-fill" {...props}></Icon>
