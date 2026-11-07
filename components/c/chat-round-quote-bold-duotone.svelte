<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0jc9qlwi.css';
import '../../css/w/wvvzy0eks.css';
import '../../css/k/kzrznpbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0jc9qlwi"/><path clip-rule="evenodd" class="wvvzy0eks"/><path clip-rule="evenodd" class="kzrznpbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-quote-bold-duotone" {...props}></Icon>
