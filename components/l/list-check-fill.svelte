<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n39gu68ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n39gu68ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-fill" {...props}></Icon>
