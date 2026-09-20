<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c22yatb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c22yatb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-box-lock-open" {...props}></Icon>
