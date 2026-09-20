<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_w-hxjse.css';
import '../../css/w/w7drs3o1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_w-hxjse"/><path class="w7drs3o1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bug" {...props}></Icon>
