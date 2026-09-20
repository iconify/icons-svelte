<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqy0o8b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hqy0o8b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:boot" {...props}></Icon>
