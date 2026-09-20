<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shwf02r4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shwf02r4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:arrow-down-left-and-arrow-up-right-to-center" {...props}></Icon>
