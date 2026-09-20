<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiwt2mb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tiwt2mb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-branch-outline" {...props}></Icon>
