<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9u81yn3y.css';
import '../../css/c/c_2y2ytjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="i9u81yn3y"/><path class="c_2y2ytjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:git-commit-outline" {...props}></Icon>
