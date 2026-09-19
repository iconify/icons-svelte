<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcg9_wbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bcg9_wbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:map-pin-ellipse" {...props}></Icon>
