<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ldd-o4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ldd-o4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelopes" {...props}></Icon>
