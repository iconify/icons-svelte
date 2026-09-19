<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbh6_gbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbh6_gbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:menu" {...props}></Icon>
