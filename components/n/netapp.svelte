<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c67s0abyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c67s0abyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:netapp" {...props}></Icon>
