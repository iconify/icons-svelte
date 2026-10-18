<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6u501b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6u501b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bazarr" {...props}></Icon>
