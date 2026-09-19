<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onl5fdbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="onl5fdbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:autoprefixer" {...props}></Icon>
