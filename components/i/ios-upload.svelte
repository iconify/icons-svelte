<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y03fodbhj.css';
import '../../css/z/z-rhwwb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y03fodbhj"/><path class="z-rhwwb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-upload" {...props}></Icon>
