<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgdu8pbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgdu8pbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up-right-square-filled" {...props}></Icon>
