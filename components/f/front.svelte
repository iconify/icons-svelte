<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lij2n1bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lij2n1bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:front" {...props}></Icon>
