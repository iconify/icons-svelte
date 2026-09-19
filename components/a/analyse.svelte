<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3m-y_svk.css';
import '../../css/d/da4kpub6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3m-y_svk"/><path class="da4kpub6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:analyse" {...props}></Icon>
