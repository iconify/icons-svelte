<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4zszezxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4zszezxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ring-spotlight-cam" {...props}></Icon>
