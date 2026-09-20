<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oki7nw3lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oki7nw3lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:luggage-solid" {...props}></Icon>
