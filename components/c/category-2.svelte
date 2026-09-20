<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9eh77vqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9eh77vqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:category-2" {...props}></Icon>
