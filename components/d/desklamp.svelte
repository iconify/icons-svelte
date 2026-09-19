<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b691pxbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="b691pxbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:desklamp" {...props}></Icon>
