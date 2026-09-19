<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-gr6gbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w-gr6gbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:buttona" {...props}></Icon>
