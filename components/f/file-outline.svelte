<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwchhybgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pwchhybgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:file-outline" {...props}></Icon>
