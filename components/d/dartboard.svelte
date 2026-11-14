<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz5ib_b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz5ib_b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dartboard" {...props}></Icon>
