<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcy4mgdjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcy4mgdjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:google" {...props}></Icon>
