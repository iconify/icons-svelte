<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pypkeqrpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pypkeqrpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:folder2" {...props}></Icon>
