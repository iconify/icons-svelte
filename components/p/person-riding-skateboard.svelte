<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1gzi36pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e1gzi36pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-skateboard" {...props}></Icon>
