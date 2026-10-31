<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbbon8b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbbon8b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:case-sensitive-round" {...props}></Icon>
