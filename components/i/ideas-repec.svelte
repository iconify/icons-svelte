<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjiwvvezl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="pjiwvvezl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ideas-repec" {...props}></Icon>
