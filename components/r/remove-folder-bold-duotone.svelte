<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2nrf10bf.css';
import '../../css/a/ae2tfkbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path class="ae2tfkbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:remove-folder-bold-duotone" {...props}></Icon>
