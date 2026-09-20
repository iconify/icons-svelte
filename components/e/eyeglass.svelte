<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awil3mfsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awil3mfsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:eyeglass" {...props}></Icon>
