<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmamszr8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gmamszr8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:edubuntu-dark" {...props}></Icon>
