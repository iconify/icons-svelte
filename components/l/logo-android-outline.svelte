<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-0a6u8qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w-0a6u8qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-android-outline" {...props}></Icon>
