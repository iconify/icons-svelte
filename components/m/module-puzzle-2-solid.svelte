<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn18cu8da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cn18cu8da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:module-puzzle-2-solid" {...props}></Icon>
