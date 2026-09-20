<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6fugovua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6fugovua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:glass-mug-variant" {...props}></Icon>
