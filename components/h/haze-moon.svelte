<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq26vi7tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq26vi7tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:haze-moon" {...props}></Icon>
