<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6e0npbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e6e0npbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-balancing" {...props}></Icon>
