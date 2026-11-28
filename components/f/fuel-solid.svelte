<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vztg8v6cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vztg8v6cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fuel-solid" {...props}></Icon>
