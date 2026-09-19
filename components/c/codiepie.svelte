<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgsbk7zch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":512};
const content = `<path class="kgsbk7zch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:codiepie" {...props}></Icon>
