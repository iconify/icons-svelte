<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grqjw4bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="grqjw4bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-up-left-box-sharp" {...props}></Icon>
