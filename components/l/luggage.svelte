<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta3apzbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta3apzbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:luggage" {...props}></Icon>
