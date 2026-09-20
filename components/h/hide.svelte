<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9st1u1pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9st1u1pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hide" {...props}></Icon>
