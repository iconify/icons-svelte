<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pej5vegmf.css';
import '../../css/s/sqh-tvbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pej5vegmf"/><path class="sqh-tvbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-crash" {...props}></Icon>
