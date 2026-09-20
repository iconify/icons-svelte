<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz58e7byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pz58e7byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cocktail" {...props}></Icon>
