<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiwnycz9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiwnycz9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-remove-light" {...props}></Icon>
