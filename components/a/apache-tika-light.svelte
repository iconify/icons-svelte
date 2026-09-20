<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adiyfh9-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="adiyfh9-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-tika-light" {...props}></Icon>
