<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omj9s4z0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="omj9s4z0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bag-pound-solid" {...props}></Icon>
