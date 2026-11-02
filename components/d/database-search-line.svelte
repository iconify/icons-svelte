<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg26o2bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg26o2bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:database-search-line" {...props}></Icon>
