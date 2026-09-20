<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc1ciyp0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc1ciyp0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:knife-blood-fill" {...props}></Icon>
