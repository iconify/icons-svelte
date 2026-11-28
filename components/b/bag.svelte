<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlamo1ykq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlamo1ykq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bag" {...props}></Icon>
