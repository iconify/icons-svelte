<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkn0u6z1h.css';
import '../../css/z/zcm3eh2ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qkn0u6z1h"/><path class="zcm3eh2ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-plus-stroke-20" {...props}></Icon>
