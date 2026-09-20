<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcq4ndq-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcq4ndq-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:apple-filled" {...props}></Icon>
