<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5k9y5r3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5k9y5r3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-branch-round" {...props}></Icon>
