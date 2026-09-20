<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy0650bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy0650bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:microphone" {...props}></Icon>
