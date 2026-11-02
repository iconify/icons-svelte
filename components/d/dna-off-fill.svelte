<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdpnaib3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdpnaib3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dna-off-fill" {...props}></Icon>
