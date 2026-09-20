<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnq5ckf1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bnq5ckf1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-dropping-trash-into-wheelie-bin" {...props}></Icon>
