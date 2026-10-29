<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6x_-9bgk.css';
import '../../css/i/i_knybbhi.css';
import '../../css/k/kw5zaebuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6x_-9bgk wm-k"/><path class="i_knybbhi wm-k"/><path class="kw5zaebuq wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:phone-off" {...props}></Icon>
