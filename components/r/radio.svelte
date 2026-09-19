<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3noic1wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3noic1wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:radio" {...props}></Icon>
