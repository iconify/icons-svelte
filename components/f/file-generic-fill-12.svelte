<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq8ar2_bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mq8ar2_bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-generic-fill-12" {...props}></Icon>
