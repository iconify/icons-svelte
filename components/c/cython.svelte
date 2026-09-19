<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emtsnsrmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="emtsnsrmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cython" {...props}></Icon>
