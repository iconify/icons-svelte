<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr6cklb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr6cklb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-spark" {...props}></Icon>
