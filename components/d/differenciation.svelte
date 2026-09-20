<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uto8vj0dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":14};
const content = `<path class="uto8vj0dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:differenciation" {...props}></Icon>
