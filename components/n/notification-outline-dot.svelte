<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8a476e8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8a476e8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:notification-outline-dot" {...props}></Icon>
