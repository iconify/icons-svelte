<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiyviqlny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiyviqlny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:google-play-solid" {...props}></Icon>
