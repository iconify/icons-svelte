<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ene56bbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ene56bbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:camera3" {...props}></Icon>
