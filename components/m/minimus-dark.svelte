<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr0pl4b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lr0pl4b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minimus-dark" {...props}></Icon>
