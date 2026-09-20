<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chyf5xbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chyf5xbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:box-off" {...props}></Icon>
