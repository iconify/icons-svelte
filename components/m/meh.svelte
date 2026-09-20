<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcbtmzz0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bcbtmzz0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:meh" {...props}></Icon>
