<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbvcw8bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rbvcw8bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-compare-outline" {...props}></Icon>
