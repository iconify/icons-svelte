<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svnli_bhv.css';
import '../../css/y/y9urdac4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="svnli_bhv"/><path class="y9urdac4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:agent-16" {...props}></Icon>
