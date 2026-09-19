<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwke2fiie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwke2fiie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-fp2" {...props}></Icon>
