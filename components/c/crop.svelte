<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np854gbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="np854gbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:crop" {...props}></Icon>
