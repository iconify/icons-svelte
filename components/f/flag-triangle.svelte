<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5_so861b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5_so861b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-triangle" {...props}></Icon>
