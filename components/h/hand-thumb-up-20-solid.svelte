<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtrpkvbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gtrpkvbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hand-thumb-up-20-solid" {...props}></Icon>
