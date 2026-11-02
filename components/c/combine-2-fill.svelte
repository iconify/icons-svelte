<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9dj5s2vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9dj5s2vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:combine-2-fill" {...props}></Icon>
