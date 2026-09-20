<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oda7t_bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oda7t_bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:love-seat" {...props}></Icon>
