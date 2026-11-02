<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq596mwtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq596mwtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:components-fill" {...props}></Icon>
