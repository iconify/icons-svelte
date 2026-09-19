<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v442e_4zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v442e_4zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-bulb" {...props}></Icon>
