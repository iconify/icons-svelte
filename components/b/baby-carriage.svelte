<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjb-ghbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjb-ghbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:baby-carriage" {...props}></Icon>
