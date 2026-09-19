<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrc_9q2ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrc_9q2ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-sub-down-left" {...props}></Icon>
