<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yes4g8bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yes4g8bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:feature-membership-filled" {...props}></Icon>
