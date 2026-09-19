<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnwirrw2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnwirrw2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:distribute-horizontal-spacing" {...props}></Icon>
