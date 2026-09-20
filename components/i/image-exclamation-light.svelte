<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skbbg-s7m.css';
import '../../css/x/xhvfopblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skbbg-s7m"/><path class="xhvfopblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-exclamation-light" {...props}></Icon>
