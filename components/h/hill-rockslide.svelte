<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oos4n-2so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="oos4n-2so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hill-rockslide" {...props}></Icon>
