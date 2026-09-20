<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wroykqb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wroykqb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-forward-bold" {...props}></Icon>
