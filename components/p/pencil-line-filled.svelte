<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrt_dqbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrt_dqbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pencil-line-filled" {...props}></Icon>
