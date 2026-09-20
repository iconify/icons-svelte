<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o89xl2b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o89xl2b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dna-2-off" {...props}></Icon>
