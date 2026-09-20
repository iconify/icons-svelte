<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p680rwbug.css';
import '../../css/p/pgldy5bla.css';
import '../../css/d/d2xewfbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p680rwbug"/><path class="pgldy5bla"/><path class="d2xewfbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand" {...props}></Icon>
