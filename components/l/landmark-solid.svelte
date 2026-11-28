<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgierebuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgierebuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:landmark-solid" {...props}></Icon>
