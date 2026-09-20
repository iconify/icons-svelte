<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcpmebi7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcpmebi7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:recording-tape-2" {...props}></Icon>
