<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcj5b4bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pcj5b4bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:anja-outline" {...props}></Icon>
