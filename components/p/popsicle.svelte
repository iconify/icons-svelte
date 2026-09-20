<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgp-5jlwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgp-5jlwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:popsicle" {...props}></Icon>
