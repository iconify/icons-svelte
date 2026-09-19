<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iath3excz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="iath3excz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:clipboard" {...props}></Icon>
