<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a45fhxbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a45fhxbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:play" {...props}></Icon>
