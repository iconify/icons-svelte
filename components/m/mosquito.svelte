<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx5qhglug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="nx5qhglug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mosquito" {...props}></Icon>
