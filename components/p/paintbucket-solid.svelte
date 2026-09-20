<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr--kk2qu.css';
import '../../css/q/q4g6dlonh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rr--kk2qu"/><path class="q4g6dlonh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:paintbucket-solid" {...props}></Icon>
