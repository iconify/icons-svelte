<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvp-8abol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvp-8abol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calculator" {...props}></Icon>
