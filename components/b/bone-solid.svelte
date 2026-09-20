<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-zp17bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="o-zp17bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bone-solid" {...props}></Icon>
