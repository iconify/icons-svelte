<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm24ldb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rm24ldb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bell-solid" {...props}></Icon>
