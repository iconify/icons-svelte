<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky2eltbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ky2eltbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:image-inverted" {...props}></Icon>
