<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdpg0fbuf.css';
import '../../css/c/c4946-17v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rdpg0fbuf"/><path class="c4946-17v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-paste-bold" {...props}></Icon>
