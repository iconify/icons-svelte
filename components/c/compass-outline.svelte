<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb14vtbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb14vtbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:compass-outline" {...props}></Icon>
