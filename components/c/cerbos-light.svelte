<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qktj-0d9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qktj-0d9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cerbos-light" {...props}></Icon>
