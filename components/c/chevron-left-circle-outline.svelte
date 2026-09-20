<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exg9pl4_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exg9pl4_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-left-circle-outline" {...props}></Icon>
