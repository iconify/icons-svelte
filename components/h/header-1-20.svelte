<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqdgwhoat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eqdgwhoat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:header-1-20" {...props}></Icon>
