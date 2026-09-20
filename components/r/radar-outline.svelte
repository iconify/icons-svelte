<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_de2x4vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_de2x4vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:radar-outline" {...props}></Icon>
