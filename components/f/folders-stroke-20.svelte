<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udxw1ou3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="udxw1ou3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:folders-stroke-20" {...props}></Icon>
