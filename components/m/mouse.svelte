<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh1wl9b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh1wl9b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:mouse" {...props}></Icon>
