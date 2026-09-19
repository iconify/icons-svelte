<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af7om7bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af7om7bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:panel-left" {...props}></Icon>
