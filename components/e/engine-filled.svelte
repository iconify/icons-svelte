<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdgvfq0gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdgvfq0gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:engine-filled" {...props}></Icon>
