<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7vux750t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7vux750t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-word-box" {...props}></Icon>
