<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sblbgjulq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sblbgjulq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:novelai" {...props}></Icon>
