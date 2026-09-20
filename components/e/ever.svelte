<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw5a_8jwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw5a_8jwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ever" {...props}></Icon>
