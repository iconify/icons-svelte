<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl672qbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="gl672qbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:block" {...props}></Icon>
