<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfxbv640g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfxbv640g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:eyeglass-off" {...props}></Icon>
