<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8be0us_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8be0us_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:quasar" {...props}></Icon>
