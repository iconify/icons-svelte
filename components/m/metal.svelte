<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag9srjboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ag9srjboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:metal" {...props}></Icon>
