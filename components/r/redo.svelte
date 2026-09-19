<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cww7r3ejt.css';
import '../../css/t/tt10iz6wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="cww7r3ejt"/><path class="tt10iz6wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:redo" {...props}></Icon>
