<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c98at3bul.css';
import '../../css/z/z4-r-ybfy.css';
import '../../css/t/t6wz8cb3t.css';
import '../../css/w/wifws7q6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c98at3bul"/><circle class="z4-r-ybfy"/><circle class="t6wz8cb3t"/><circle class="wifws7q6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:dice-3" {...props}></Icon>
