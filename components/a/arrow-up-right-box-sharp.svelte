<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt4r-82jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xt4r-82jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-up-right-box-sharp" {...props}></Icon>
