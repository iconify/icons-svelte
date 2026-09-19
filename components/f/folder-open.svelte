<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpq9aybfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpq9aybfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-open" {...props}></Icon>
