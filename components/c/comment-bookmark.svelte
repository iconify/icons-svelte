<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsyn_yf4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsyn_yf4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-bookmark" {...props}></Icon>
