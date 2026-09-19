<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsum-u5pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hsum-u5pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:adobe-premiere" {...props}></Icon>
