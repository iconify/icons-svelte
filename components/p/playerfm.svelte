<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k57p5qbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k57p5qbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:playerfm" {...props}></Icon>
