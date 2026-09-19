<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke8hbtb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke8hbtb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pen-off" {...props}></Icon>
