<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxb0y9l6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxb0y9l6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-dollar" {...props}></Icon>
