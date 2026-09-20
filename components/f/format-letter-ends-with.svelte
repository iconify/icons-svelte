<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5zp4067s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5zp4067s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-letter-ends-with" {...props}></Icon>
