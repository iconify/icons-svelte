<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t732w_hqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t732w_hqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bevy" {...props}></Icon>
