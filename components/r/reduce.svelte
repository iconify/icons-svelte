<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyo_5k1_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyo_5k1_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:reduce" {...props}></Icon>
