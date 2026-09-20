<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h48013zuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h48013zuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:akaunting-dark" {...props}></Icon>
