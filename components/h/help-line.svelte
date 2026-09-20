<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mstlozbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mstlozbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:help-line" {...props}></Icon>
