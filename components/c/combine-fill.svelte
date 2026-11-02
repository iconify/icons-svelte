<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvpt0wbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvpt0wbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:combine-fill" {...props}></Icon>
