<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh8av2-8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh8av2-8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-left-fill-round" {...props}></Icon>
