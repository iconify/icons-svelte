<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/encv9kbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":288,"height":512};
const content = `<path class="encv9kbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dollar-sign" {...props}></Icon>
