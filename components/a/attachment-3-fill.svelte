<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mco0w3z_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mco0w3z_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:attachment-3-fill" {...props}></Icon>
