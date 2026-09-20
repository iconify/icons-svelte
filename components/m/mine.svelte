<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g21yy3i8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g21yy3i8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mine" {...props}></Icon>
