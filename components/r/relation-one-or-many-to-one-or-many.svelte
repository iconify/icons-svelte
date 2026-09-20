<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiabbsb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uiabbsb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-one-or-many-to-one-or-many" {...props}></Icon>
