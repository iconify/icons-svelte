<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7mn-8b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7mn-8b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:pentagon" {...props}></Icon>
