<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzchkyb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzchkyb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:2n" {...props}></Icon>
