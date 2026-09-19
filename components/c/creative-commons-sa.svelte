<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o03oq3bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o03oq3bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:creative-commons-sa" {...props}></Icon>
