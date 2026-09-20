<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbn7w4b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbn7w4b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pipx" {...props}></Icon>
