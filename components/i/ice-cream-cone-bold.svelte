<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr7tf6sse.css';
import '../../css/t/tf3fnbb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr7tf6sse"/><path class="tf3fnbb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:ice-cream-cone-bold" {...props}></Icon>
