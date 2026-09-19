<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvlvc6h1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pvlvc6h1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:people-carry" {...props}></Icon>
