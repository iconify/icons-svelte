<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkmuvyw1o.css';
import '../../css/a/a_ls9acgf.css';
import '../../css/n/nu2_-nbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="xkmuvyw1o"/><path class="a_ls9acgf"/><path class="nu2_-nbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-hazard" {...props}></Icon>
