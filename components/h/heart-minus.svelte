<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3-qm7g3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3-qm7g3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:heart-minus" {...props}></Icon>
