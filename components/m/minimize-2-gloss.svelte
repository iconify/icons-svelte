<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvq7y5bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvq7y5bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:minimize-2-gloss" {...props}></Icon>
