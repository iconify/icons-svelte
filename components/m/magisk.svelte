<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp4a3ib0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cp4a3ib0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:magisk" {...props}></Icon>
