<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bae35fb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bae35fb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-branch-solid" {...props}></Icon>
