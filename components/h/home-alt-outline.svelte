<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxx3bu1xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bxx3bu1xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:home-alt-outline" {...props}></Icon>
