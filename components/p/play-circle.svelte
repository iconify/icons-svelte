<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq2lz_ujg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq2lz_ujg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-circle" {...props}></Icon>
