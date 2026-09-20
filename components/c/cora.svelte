<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm0zfnzip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm0zfnzip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cora" {...props}></Icon>
