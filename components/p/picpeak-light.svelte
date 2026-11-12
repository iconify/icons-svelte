<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdqqpp0kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rdqqpp0kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:picpeak-light" {...props}></Icon>
