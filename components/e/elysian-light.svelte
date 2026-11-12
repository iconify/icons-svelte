<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4oiss6dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e4oiss6dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:elysian-light" {...props}></Icon>
