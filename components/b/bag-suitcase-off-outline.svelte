<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_a0i2ghy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_a0i2ghy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bag-suitcase-off-outline" {...props}></Icon>
