<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dft_mutud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dft_mutud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:cloud-snow" {...props}></Icon>
