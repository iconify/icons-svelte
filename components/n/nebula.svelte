<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8rfl0h4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8rfl0h4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nebula" {...props}></Icon>
