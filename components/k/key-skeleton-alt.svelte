<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqft92biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqft92biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:key-skeleton-alt" {...props}></Icon>
