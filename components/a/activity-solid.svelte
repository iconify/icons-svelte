<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjg6l7blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjg6l7blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:activity-solid" {...props}></Icon>
