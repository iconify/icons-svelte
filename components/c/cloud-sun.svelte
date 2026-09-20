<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls0nprbji.css';
import '../../css/u/uo-66kwym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="ls0nprbji"/><path clip-rule="evenodd" class="uo-66kwym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-sun" {...props}></Icon>
