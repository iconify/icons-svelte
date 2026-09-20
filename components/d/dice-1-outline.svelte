<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtoae-bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtoae-bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-1-outline" {...props}></Icon>
