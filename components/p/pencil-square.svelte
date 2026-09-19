<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfuy65bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfuy65bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pencil-square" {...props}></Icon>
