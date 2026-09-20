<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opj97bpgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opj97bpgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:discount" {...props}></Icon>
