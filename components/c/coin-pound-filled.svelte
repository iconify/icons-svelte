<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa714cinw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wa714cinw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:coin-pound-filled" {...props}></Icon>
