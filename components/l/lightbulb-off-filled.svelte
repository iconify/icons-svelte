<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvf-d1baf.css';
import '../../css/c/cs8o81b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvf-d1baf"/><path class="cs8o81b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lightbulb-off-filled" {...props}></Icon>
