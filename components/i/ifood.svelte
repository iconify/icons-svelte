<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anhbliouf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anhbliouf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ifood" {...props}></Icon>
