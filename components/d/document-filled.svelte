<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nilwtjblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nilwtjblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:document-filled" {...props}></Icon>
