<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-x5_513g.css';
import '../../css/c/c4km1paud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j-x5_513g"/><path class="c4km1paud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fusion-48-bold" {...props}></Icon>
