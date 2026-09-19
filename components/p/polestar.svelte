<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwev2pbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwev2pbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:polestar" {...props}></Icon>
