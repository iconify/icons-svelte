<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjylmac8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjylmac8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:escalator-down-person" {...props}></Icon>
