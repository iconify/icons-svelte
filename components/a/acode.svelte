<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq32u3btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq32u3btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:acode" {...props}></Icon>
