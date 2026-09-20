<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwdjlwbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nwdjlwbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:key-return-noframe-16" {...props}></Icon>
