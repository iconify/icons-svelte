<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czo9m703j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="czo9m703j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hourglass-half" {...props}></Icon>
