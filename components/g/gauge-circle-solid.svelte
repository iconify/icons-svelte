<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv1hcrjrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv1hcrjrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gauge-circle-solid" {...props}></Icon>
