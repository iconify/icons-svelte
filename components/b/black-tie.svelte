<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7-gf6ssk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="b7-gf6ssk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:black-tie" {...props}></Icon>
