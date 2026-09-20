<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i76rxtbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i76rxtbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:layers-sharp" {...props}></Icon>
