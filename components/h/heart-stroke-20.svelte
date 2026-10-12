<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sut_o-gje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sut_o-gje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:heart-stroke-20" {...props}></Icon>
