<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwlqnablk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwlqnablk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:moustache" {...props}></Icon>
