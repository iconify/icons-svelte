<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd6li47sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wd6li47sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:coffee-bean-solid" {...props}></Icon>
