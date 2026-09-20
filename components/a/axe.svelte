<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac-i-ib1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ac-i-ib1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:axe" {...props}></Icon>
