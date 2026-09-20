<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b84sy2bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b84sy2bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pencil-ruler" {...props}></Icon>
