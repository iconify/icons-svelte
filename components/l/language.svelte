<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no8scmbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="no8scmbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:language" {...props}></Icon>
