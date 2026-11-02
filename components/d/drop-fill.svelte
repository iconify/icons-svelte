<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tva70obqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tva70obqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drop-fill" {...props}></Icon>
