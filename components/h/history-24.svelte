<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hohcf3gsm.css';
import '../../css/b/bmavll4ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hohcf3gsm"/><path class="bmavll4ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:history-24" {...props}></Icon>
