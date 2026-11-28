<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjqn1y8dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjqn1y8dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:phi-solid" {...props}></Icon>
