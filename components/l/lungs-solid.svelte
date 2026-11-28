<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obtnb0bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obtnb0bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lungs-solid" {...props}></Icon>
