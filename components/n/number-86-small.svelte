<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6cof4bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6cof4bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-86-small" {...props}></Icon>
