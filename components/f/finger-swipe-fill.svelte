<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw6c2jk0b.css';
import '../../css/j/j1j4zhbfy.css';
import '../../css/g/gocw17-6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mw6c2jk0b"/><path class="j1j4zhbfy"/><path class="gocw17-6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-swipe-fill" {...props}></Icon>
