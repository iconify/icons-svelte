<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak69pm-aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ak69pm-aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:astuto-light" {...props}></Icon>
