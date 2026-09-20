<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0rxk3bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0rxk3bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-edit" {...props}></Icon>
