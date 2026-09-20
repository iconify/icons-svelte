<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_-9aua6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_-9aua6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:drag-indicator-line" {...props}></Icon>
