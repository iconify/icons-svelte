<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqi4pnbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uqi4pnbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:briefcase" {...props}></Icon>
