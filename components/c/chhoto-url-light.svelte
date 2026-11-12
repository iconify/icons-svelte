<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtbeadc0j.css';
import '../../css/h/h_f86fbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mtbeadc0j"/><path class="h_f86fbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chhoto-url-light" {...props}></Icon>
