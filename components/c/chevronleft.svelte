<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9echc66j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="q9echc66j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:chevronleft" {...props}></Icon>
