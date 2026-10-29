<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baz9wuw8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="baz9wuw8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-a" {...props}></Icon>
