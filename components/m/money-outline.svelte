<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di7af1s5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="di7af1s5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:money-outline" {...props}></Icon>
