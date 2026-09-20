<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkti_bbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkti_bbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:popcorn" {...props}></Icon>
