<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvc87pa5f.css';
import '../../css/o/os561700d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rvc87pa5f"/><path class="os561700d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-repeat" {...props}></Icon>
