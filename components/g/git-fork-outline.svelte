<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwkw_ebhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zwkw_ebhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-fork-outline" {...props}></Icon>
