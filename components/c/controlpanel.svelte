<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e74zqbzmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="e74zqbzmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:controlpanel" {...props}></Icon>
