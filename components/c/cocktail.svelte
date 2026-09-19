<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtqpr-xro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":472};
const content = `<path class="dtqpr-xro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:cocktail" {...props}></Icon>
