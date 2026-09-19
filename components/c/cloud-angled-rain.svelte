<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rugsg9zlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rugsg9zlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-angled-rain" {...props}></Icon>
