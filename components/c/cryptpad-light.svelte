<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymzz4rb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ymzz4rb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cryptpad-light" {...props}></Icon>
