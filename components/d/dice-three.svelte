<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zho1-hbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zho1-hbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dice-three" {...props}></Icon>
