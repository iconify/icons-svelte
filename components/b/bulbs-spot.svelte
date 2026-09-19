<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x997jeb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x997jeb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulbs-spot" {...props}></Icon>
