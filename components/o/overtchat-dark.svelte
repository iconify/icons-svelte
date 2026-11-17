<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_r83otwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n_r83otwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:overtchat-dark" {...props}></Icon>
