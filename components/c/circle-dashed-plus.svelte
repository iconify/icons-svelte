<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr0l9189m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr0l9189m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-plus" {...props}></Icon>
