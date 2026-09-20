<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwx2ffbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="qwx2ffbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:religious-jewish-11" {...props}></Icon>
