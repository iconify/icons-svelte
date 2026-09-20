<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzc7ujhxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bzc7ujhxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:bank-14" {...props}></Icon>
