<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnuqs-t7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnuqs-t7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:cloth" {...props}></Icon>
