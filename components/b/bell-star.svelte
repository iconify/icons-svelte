<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htpn1ob9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htpn1ob9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-star" {...props}></Icon>
