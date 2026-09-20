<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3lnl39gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3lnl39gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:escalator-up" {...props}></Icon>
