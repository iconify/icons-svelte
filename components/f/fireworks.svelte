<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wop2_bcbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wop2_bcbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fireworks" {...props}></Icon>
