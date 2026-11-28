<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4mx0ujya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4mx0ujya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-solid" {...props}></Icon>
