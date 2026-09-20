<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-fx9vqjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y-fx9vqjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-carrying-ski-and-ski-poles" {...props}></Icon>
