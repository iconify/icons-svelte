<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md8_qczcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md8_qczcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-up-left-round" {...props}></Icon>
