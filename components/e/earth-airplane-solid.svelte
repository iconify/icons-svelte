<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv0wjcc0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mv0wjcc0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:earth-airplane-solid" {...props}></Icon>
