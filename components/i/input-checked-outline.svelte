<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/augh1ex2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="augh1ex2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:input-checked-outline" {...props}></Icon>
