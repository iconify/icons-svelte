<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3d7yhb3u.css';
import '../../css/m/m9_h30bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3d7yhb3u"/><path class="m9_h30bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gate-io" {...props}></Icon>
