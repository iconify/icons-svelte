<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4f65egzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4f65egzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:logtide-light" {...props}></Icon>
