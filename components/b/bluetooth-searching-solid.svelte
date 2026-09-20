<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v11pwac-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v11pwac-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bluetooth-searching-solid" {...props}></Icon>
