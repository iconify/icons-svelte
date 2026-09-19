<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdn2mabuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zdn2mabuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:annotate" {...props}></Icon>
