<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8ha2hsdr.css';
import '../../css/a/aby3u3bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8ha2hsdr"/><path class="aby3u3bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:door-open-alt" {...props}></Icon>
