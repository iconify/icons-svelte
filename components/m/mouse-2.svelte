<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nep_g5q_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nep_g5q_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mouse-2" {...props}></Icon>
