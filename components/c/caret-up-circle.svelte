<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijg5zh-jo.css';
import '../../css/w/wqbkv8u2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijg5zh-jo"/><path class="wqbkv8u2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:caret-up-circle" {...props}></Icon>
