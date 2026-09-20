<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu47fn-nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu47fn-nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drag-drop-line" {...props}></Icon>
