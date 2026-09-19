<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2u4dz6lg.css';
import '../../css/t/t6wjn2ega.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2u4dz6lg"/><path clip-rule="evenodd" class="t6wjn2ega"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:reddit-outline" {...props}></Icon>
