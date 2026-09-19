<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tisqd0b5c.css';
import '../../css/d/d4z24ff_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":16};
const content = `<path class="tisqd0b5c"/><path class="d4z24ff_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:flag" {...props}></Icon>
