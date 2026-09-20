<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xywj-_bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xywj-_bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arrow-alt-lright" {...props}></Icon>
