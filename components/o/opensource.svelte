<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkerobcrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":991};
const content = `<path class="jkerobcrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:opensource" {...props}></Icon>
