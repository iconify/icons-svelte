<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi221rtgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zi221rtgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:networking-toolbox-light" {...props}></Icon>
