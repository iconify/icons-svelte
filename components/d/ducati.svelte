<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldin_cbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldin_cbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ducati" {...props}></Icon>
