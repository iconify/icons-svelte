<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo3g6abcw.css';
import '../../css/w/wvyu5ibqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fo3g6abcw"/><path class="wvyu5ibqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:login-2-bold" {...props}></Icon>
