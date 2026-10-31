<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-kprpgwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-kprpgwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-off-round" {...props}></Icon>
