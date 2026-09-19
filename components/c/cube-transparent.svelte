<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enalfn1yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enalfn1yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cube-transparent" {...props}></Icon>
