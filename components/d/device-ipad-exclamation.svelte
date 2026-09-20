<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qav90nb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qav90nb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-exclamation" {...props}></Icon>
