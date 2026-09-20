<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kur-1kb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kur-1kb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:angle-left" {...props}></Icon>
