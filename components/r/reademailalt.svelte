<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-bdumbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="r-bdumbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:reademailalt" {...props}></Icon>
