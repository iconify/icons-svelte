<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_5fgbyrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_5fgbyrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:join-straight" {...props}></Icon>
