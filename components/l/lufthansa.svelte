<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqk-beb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqk-beb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lufthansa" {...props}></Icon>
