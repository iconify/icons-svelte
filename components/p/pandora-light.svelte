<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig8ne5sll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ig8ne5sll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pandora-light" {...props}></Icon>
