<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmkrdm4ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vmkrdm4ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:call-out" {...props}></Icon>
