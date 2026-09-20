<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwucx9qju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dwucx9qju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aureus-light" {...props}></Icon>
