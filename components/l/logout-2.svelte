<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_huerbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_huerbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:logout-2" {...props}></Icon>
