<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijg5zh-jo.css';
import '../../css/c/c98at3bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijg5zh-jo"/><path class="c98at3bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:caret-up-square" {...props}></Icon>
