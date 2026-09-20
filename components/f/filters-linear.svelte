<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h29j--52h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h29j--52h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filters-linear" {...props}></Icon>
