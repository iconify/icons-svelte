<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svb-z_tut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="svb-z_tut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:artstation" {...props}></Icon>
