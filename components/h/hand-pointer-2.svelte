<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvn3hubuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvn3hubuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:hand-pointer-2" {...props}></Icon>
