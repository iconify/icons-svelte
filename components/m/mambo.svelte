<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afltnac5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":896};
const content = `<path class="afltnac5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mambo" {...props}></Icon>
