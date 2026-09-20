<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9s9u9bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9s9u9bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:drag-indicator-fill" {...props}></Icon>
