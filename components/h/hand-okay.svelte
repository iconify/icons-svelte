<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd7x03eky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd7x03eky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-okay" {...props}></Icon>
