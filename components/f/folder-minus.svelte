<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-acgjbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-acgjbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:folder-minus" {...props}></Icon>
