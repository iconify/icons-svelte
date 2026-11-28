<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrw5j1c7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrw5j1c7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:alert-double-solid" {...props}></Icon>
