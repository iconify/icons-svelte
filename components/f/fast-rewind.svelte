<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5bt8w1cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5bt8w1cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fast-rewind" {...props}></Icon>
