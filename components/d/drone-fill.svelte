<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5mogn6wk.css';
import '../../css/z/ziwtbxb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5mogn6wk"/><path class="ziwtbxb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drone-fill" {...props}></Icon>
