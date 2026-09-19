<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd1f270-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd1f270-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:battery-charging" {...props}></Icon>
