<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whuxrvbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whuxrvbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-fork-round" {...props}></Icon>
