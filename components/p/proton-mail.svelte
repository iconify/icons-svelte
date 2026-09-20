<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5fwsnbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5fwsnbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:proton-mail" {...props}></Icon>
