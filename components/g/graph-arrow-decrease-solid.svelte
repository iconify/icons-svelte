<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyz20i6jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tyz20i6jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:graph-arrow-decrease-solid" {...props}></Icon>
