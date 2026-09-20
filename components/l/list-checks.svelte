<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucnvjn25j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucnvjn25j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:list-checks" {...props}></Icon>
