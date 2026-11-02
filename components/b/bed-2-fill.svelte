<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr1435t9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr1435t9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bed-2-fill" {...props}></Icon>
