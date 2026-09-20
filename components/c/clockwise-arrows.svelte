<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owsuyko8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owsuyko8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clockwise-arrows" {...props}></Icon>
