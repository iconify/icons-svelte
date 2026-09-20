<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp_eem7eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp_eem7eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-sharp-fill" {...props}></Icon>
