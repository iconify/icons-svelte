<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-5sx6b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="d-5sx6b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pumpjack" {...props}></Icon>
