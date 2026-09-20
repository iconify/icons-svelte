<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9yk_g8pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9yk_g8pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file" {...props}></Icon>
