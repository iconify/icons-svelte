<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjjcb30vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjjcb30vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:playstation" {...props}></Icon>
