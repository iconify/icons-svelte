<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm7qjnegn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qm7qjnegn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:minus" {...props}></Icon>
