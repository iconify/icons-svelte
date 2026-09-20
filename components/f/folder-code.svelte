<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqe5ph00n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqe5ph00n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-code" {...props}></Icon>
