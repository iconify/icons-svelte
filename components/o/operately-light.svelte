<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whdlzbczh.css';
import '../../css/v/vas3oxb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="whdlzbczh"/><path class="vas3oxb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:operately-light" {...props}></Icon>
