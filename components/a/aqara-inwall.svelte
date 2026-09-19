<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap6ub7b7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap6ub7b7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-inwall" {...props}></Icon>
