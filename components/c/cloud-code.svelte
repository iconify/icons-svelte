<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm3aaq-yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm3aaq-yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-code" {...props}></Icon>
