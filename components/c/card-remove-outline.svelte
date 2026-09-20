<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flf719bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flf719bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-remove-outline" {...props}></Icon>
