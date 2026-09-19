<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptmn2cc3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ptmn2cc3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pluscircles" {...props}></Icon>
