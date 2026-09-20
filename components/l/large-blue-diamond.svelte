<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6gwf2-xb.css';
import '../../css/o/o_t_4_bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="z6gwf2-xb"/><path class="o_t_4_bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:large-blue-diamond" {...props}></Icon>
