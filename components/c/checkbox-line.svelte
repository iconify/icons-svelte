<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl1uuu-xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl1uuu-xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:checkbox-line" {...props}></Icon>
