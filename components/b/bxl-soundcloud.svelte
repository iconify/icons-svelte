<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kldny2m9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kldny2m9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-soundcloud" {...props}></Icon>
