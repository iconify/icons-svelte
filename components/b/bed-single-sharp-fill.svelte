<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcig4fbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcig4fbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bed-single-sharp-fill" {...props}></Icon>
