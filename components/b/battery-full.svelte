<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wco7hpz_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wco7hpz_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:battery-full" {...props}></Icon>
