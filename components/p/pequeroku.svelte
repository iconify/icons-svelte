<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0jsy2bsu.css';
import '../../css/u/u8orx1b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0jsy2bsu"/><path class="u8orx1b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pequeroku" {...props}></Icon>
