<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd7hg6b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rd7hg6b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-office-light" {...props}></Icon>
