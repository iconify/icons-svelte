<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv9tauant.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv9tauant"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:contract-clock" {...props}></Icon>
