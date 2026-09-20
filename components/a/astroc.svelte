<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz3cb7byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tz3cb7byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:astroc" {...props}></Icon>
