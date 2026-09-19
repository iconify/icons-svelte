<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa3vor71a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wa3vor71a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:battery" {...props}></Icon>
