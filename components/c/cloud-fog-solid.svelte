<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/husiggbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="husiggbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-fog-solid" {...props}></Icon>
