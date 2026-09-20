<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev65m7dkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev65m7dkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pentagon" {...props}></Icon>
