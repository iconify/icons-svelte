<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzt6r2bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzt6r2bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-search-line" {...props}></Icon>
