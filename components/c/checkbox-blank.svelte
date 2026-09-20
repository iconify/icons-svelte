<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oprx6eucf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oprx6eucf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkbox-blank" {...props}></Icon>
