<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abjqn5hlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="abjqn5hlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-right-to-rectangle-tall-outline" {...props}></Icon>
