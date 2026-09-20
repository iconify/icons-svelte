<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcn9u5-6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcn9u5-6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mingcute-fill" {...props}></Icon>
