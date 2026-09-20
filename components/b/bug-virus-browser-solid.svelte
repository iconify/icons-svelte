<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tejqw0big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tejqw0big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bug-virus-browser-solid" {...props}></Icon>
