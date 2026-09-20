<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-m9x5g6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l-m9x5g6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:bell" {...props}></Icon>
