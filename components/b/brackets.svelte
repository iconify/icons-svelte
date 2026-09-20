<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0mzb2gdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0mzb2gdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brackets" {...props}></Icon>
