<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2mpx0jfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2mpx0jfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-n" {...props}></Icon>
