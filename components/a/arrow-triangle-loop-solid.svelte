<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3mk2sb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3mk2sb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-triangle-loop-solid" {...props}></Icon>
