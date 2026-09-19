<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxh8uybpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kxh8uybpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:goblet" {...props}></Icon>
