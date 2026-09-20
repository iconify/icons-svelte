<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6b198eng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6b198eng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pout-filled" {...props}></Icon>
