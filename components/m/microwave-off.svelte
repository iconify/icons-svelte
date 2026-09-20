<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asz9aeb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asz9aeb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microwave-off" {...props}></Icon>
