<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlzfj5w3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zlzfj5w3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:medium-outline" {...props}></Icon>
