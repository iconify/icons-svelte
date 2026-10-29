<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1iz3pbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1iz3pbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-j" {...props}></Icon>
