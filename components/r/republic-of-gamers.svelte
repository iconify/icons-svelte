<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lisdfkbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lisdfkbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:republic-of-gamers" {...props}></Icon>
