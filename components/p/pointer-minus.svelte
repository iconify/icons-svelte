<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2_j8acfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2_j8acfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-minus" {...props}></Icon>
