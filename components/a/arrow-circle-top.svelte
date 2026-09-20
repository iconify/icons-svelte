<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlytjccmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hlytjccmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:arrow-circle-top" {...props}></Icon>
