<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpakxm-mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpakxm-mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pin-plus" {...props}></Icon>
