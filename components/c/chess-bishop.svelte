<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wntc1qbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wntc1qbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:chess-bishop" {...props}></Icon>
