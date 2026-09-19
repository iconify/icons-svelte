<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4aol_b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4aol_b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-add-bold" {...props}></Icon>
