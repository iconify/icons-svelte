<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phqtgzqdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phqtgzqdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-heart-outline" {...props}></Icon>
