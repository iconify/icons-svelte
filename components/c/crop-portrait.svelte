<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9_kftbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9_kftbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:crop-portrait" {...props}></Icon>
