<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q734u6b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q734u6b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-down-square-solid" {...props}></Icon>
