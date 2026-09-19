<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkex5867a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bkex5867a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:redefinition" {...props}></Icon>
