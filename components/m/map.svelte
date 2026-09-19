<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn_wtjb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn_wtjb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:map" {...props}></Icon>
