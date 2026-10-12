<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l91gf31ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l91gf31ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:connector-fill-20" {...props}></Icon>
