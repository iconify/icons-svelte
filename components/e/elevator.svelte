<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea_zpbnow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ea_zpbnow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:elevator" {...props}></Icon>
