<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grt6yzcqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grt6yzcqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-sharp-duo" {...props}></Icon>
