<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2je18u3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s2je18u3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:drink-can-and-drink-bottle" {...props}></Icon>
