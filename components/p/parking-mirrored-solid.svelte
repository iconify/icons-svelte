<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guoec1bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="guoec1bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:parking-mirrored-solid" {...props}></Icon>
