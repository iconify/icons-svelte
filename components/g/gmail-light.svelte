<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv0ctzb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kv0ctzb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gmail-light" {...props}></Icon>
