<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr2j3nbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr2j3nbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:airplay" {...props}></Icon>
