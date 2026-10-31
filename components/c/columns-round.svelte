<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmksrjkpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmksrjkpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:columns-round" {...props}></Icon>
