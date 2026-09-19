<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azman8bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="azman8bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:goblet-square" {...props}></Icon>
