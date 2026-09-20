<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myv-mghnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="myv-mghnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cabin" {...props}></Icon>
