<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h59o814uu.css';
import '../../css/l/l9_rs7bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h59o814uu"/><path class="l9_rs7bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:library" {...props}></Icon>
