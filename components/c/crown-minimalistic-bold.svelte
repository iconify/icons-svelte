<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej9tf-bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej9tf-bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crown-minimalistic-bold" {...props}></Icon>
