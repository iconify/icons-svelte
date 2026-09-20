<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecdj5xkhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ecdj5xkhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:respirator" {...props}></Icon>
