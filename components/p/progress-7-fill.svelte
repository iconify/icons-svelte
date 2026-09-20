<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i64g3g2nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i64g3g2nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-7-fill" {...props}></Icon>
