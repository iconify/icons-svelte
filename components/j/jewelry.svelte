<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpxjk91ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lpxjk91ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:jewelry" {...props}></Icon>
