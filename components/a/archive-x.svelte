<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk3763b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk3763b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:archive-x" {...props}></Icon>
