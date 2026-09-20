<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwrb4ybqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qwrb4ybqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aliasvault-dark" {...props}></Icon>
