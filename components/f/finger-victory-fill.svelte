<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m14puibhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m14puibhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-victory-fill" {...props}></Icon>
