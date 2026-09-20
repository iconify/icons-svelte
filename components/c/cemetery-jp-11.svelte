<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoph2sbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="zoph2sbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:cemetery-jp-11" {...props}></Icon>
