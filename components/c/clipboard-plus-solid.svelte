<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghqo2s4pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghqo2s4pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:clipboard-plus-solid" {...props}></Icon>
